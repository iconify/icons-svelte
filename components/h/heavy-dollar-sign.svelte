<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du7ckob0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="du7ckob0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:heavy-dollar-sign" {...props}></Icon>
