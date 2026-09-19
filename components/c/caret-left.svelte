<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpz30suta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mpz30suta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:caret-left" {...props}></Icon>
