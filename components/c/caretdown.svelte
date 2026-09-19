<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6r3qwg2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":9};
const content = `<path class="f6r3qwg2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:caretdown" {...props}></Icon>
