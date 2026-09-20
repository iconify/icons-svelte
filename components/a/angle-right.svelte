<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlt2f1bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlt2f1bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:angle-right" {...props}></Icon>
