<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mrli8m4nv.css';
import '../../css/b/bly0oihkk.css';
import '../../css/v/v88mtsb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="mrli8m4nv"/><path class="bly0oihkk"/><path class="v88mtsb4v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lasso" {...props}></Icon>
