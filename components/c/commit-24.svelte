<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp5ysukwo.css';
import '../../css/r/rve223_3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp5ysukwo"/><path class="rve223_3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:commit-24" {...props}></Icon>
