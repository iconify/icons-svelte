<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r64x3ubrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="r64x3ubrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:loadbar" {...props}></Icon>
