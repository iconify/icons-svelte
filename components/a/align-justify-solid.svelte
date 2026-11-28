<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cif9nhx3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cif9nhx3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-justify-solid" {...props}></Icon>
