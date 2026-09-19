<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aax8d_bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aax8d_bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:close-md" {...props}></Icon>
