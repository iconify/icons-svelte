<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrdnb5auz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdnb5auz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:convert-filled" {...props}></Icon>
