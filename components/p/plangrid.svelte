<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2iwa8ist.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2iwa8ist"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:plangrid" {...props}></Icon>
