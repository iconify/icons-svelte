<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbt4c8ptk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt4c8ptk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:albert-heijn" {...props}></Icon>
