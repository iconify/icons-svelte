<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdnfh8bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hdnfh8bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dna" {...props}></Icon>
