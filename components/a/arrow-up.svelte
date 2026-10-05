<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsod67gbj.css';
import '../../css/r/rc7mtqb4o.css';
import '../../css/y/y0wqglbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="rsod67gbj"><path class="rc7mtqb4o"/><path class="y0wqglbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:arrow-up" {...props}></Icon>
