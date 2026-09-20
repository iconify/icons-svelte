<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o98vbdcga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o98vbdcga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:pet-animals-dog" {...props}></Icon>
