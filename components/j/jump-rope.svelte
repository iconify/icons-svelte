<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thj6iccmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thj6iccmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:jump-rope" {...props}></Icon>
