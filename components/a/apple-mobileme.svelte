<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-n2gk5jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-n2gk5jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-mobileme" {...props}></Icon>
