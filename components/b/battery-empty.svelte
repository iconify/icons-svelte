<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_i3iqatv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_i3iqatv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:battery-empty" {...props}></Icon>
