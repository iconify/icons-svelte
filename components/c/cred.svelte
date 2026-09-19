<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu0ok6bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yu0ok6bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cred" {...props}></Icon>
