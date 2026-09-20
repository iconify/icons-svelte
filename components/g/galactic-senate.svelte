<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh55owlqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nh55owlqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:galactic-senate" {...props}></Icon>
