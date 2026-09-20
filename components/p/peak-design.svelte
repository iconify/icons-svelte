<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c06w4lbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c06w4lbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:peak-design" {...props}></Icon>
