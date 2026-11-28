<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkuj69bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dkuj69bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:letter-spacing-light" {...props}></Icon>
