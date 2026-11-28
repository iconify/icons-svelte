<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-ccbcur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-ccbcur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-star-solid" {...props}></Icon>
