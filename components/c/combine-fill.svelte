<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy4ndbb0i.css';
import '../../css/u/uszgsoqps.css';
import '../../css/j/jmec2jscz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy4ndbb0i"/><path class="uszgsoqps"/><path class="jmec2jscz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:combine-fill" {...props}></Icon>
