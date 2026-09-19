<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ococizr3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ococizr3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:protonmail" {...props}></Icon>
