<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxgsmd1pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uxgsmd1pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:black-large-square" {...props}></Icon>
