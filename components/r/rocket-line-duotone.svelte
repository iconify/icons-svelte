<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f3oj9ibrq.css';
import '../../css/h/hmsxxdbnu.css';
import '../../css/i/icj9c585j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f3oj9ibrq"/><path class="hmsxxdbnu"/><path class="icj9c585j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-line-duotone" {...props}></Icon>
