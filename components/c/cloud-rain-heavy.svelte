<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z687y3m2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z687y3m2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-rain-heavy" {...props}></Icon>
