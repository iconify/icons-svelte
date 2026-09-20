<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnpa_2wmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnpa_2wmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-line" {...props}></Icon>
