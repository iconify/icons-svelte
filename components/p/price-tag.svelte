<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oih079b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oih079b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:price-tag" {...props}></Icon>
