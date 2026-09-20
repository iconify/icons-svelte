<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0c-s5bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0c-s5bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:comptia" {...props}></Icon>
