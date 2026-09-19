<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd9r3qbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cd9r3qbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:repv2" {...props}></Icon>
