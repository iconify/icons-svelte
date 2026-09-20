<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbpyxnsjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bbpyxnsjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hearts-symbol-solid" {...props}></Icon>
