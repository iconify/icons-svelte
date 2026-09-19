<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdzi00bpt.css';
import '../../css/y/y96pjh_pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="y96pjh_pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-chart" {...props}></Icon>
