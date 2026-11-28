<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csw3b1buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csw3b1buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dropdown" {...props}></Icon>
