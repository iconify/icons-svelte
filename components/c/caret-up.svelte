<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfi2grt-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfi2grt-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-up" {...props}></Icon>
