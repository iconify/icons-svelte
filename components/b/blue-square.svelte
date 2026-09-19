<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teeg0uhoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="teeg0uhoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:blue-square" {...props}></Icon>
