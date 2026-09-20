<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xukjylo-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xukjylo-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar2-filled" {...props}></Icon>
