<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhe1fhswa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhe1fhswa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-vertical-square-fill" {...props}></Icon>
