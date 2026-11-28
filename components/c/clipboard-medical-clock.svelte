<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9e_3fb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9e_3fb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-medical-clock" {...props}></Icon>
