<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5jmlecrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5jmlecrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:elgato" {...props}></Icon>
