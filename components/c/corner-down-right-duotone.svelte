<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4-p-l7oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4-p-l7oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-down-right-duotone" {...props}></Icon>
