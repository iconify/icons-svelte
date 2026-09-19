<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6n136b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v6n136b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-typekit" {...props}></Icon>
