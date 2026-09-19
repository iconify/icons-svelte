<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgh3h12lr.css';
import '../../css/f/fmv_7cgeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgh3h12lr"/><path class="fmv_7cgeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:left-top-arrow-circle" {...props}></Icon>
