<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq83s-bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq83s-bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-up" {...props}></Icon>
