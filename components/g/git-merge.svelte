<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoqel95_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqel95_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:git-merge" {...props}></Icon>
