<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znnub8yeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znnub8yeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-lock" {...props}></Icon>
