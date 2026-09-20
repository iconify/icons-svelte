<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm1oe6iah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="cm1oe6iah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:framer-light" {...props}></Icon>
