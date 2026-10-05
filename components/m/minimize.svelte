<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/cddtx52ge.css';
import '../../css/n/nab1kbbwm.css';
import '../../css/h/hnxj6fbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="cddtx52ge"/><path class="nab1kbbwm"/><path class="hnxj6fbkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:minimize" {...props}></Icon>
