<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajqbr35kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ajqbr35kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:double-chevron-left" {...props}></Icon>
