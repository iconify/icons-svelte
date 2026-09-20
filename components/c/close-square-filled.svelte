<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmexoo1yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmexoo1yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:close-square-filled" {...props}></Icon>
