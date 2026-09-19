<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1dcbxwrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":620,"height":753};
const content = `<path class="c1dcbxwrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:m-upper-case" {...props}></Icon>
