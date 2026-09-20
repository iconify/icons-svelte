<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqrdo_rwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqrdo_rwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:moon-light" {...props}></Icon>
