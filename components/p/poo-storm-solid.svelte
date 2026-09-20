<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5qdc0b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n5qdc0b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:poo-storm-solid" {...props}></Icon>
