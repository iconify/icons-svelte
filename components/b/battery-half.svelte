<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-0pk97dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-0pk97dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:battery-half" {...props}></Icon>
