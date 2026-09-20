<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrzww_a4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrzww_a4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nubank" {...props}></Icon>
