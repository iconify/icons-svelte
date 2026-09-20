<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weuc8pb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weuc8pb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:activity" {...props}></Icon>
