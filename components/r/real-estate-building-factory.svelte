<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t02gsl99c.css';
import '../../css/i/ipce-91ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t02gsl99c"/><path class="ipce-91ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:real-estate-building-factory" {...props}></Icon>
