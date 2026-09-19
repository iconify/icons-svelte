<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2eafcbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2eafcbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:eos" {...props}></Icon>
