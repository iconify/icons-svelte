<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9bmbabmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9bmbabmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:resurrection-remix-os" {...props}></Icon>
