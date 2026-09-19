<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3qskuahn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z3qskuahn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-google" {...props}></Icon>
