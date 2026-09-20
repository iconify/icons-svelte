<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_8qcubwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="n_8qcubwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:reset" {...props}></Icon>
