<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwhuilbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwhuilbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:backspace-fill" {...props}></Icon>
