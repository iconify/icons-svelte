<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubbzq5eml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":160,"height":384};
const content = `<path class="ubbzq5eml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:chevron-right" {...props}></Icon>
