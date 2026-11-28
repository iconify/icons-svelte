<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z969ijbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z969ijbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:border-inside-solid" {...props}></Icon>
