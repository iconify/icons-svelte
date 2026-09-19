<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dodm8zeqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dodm8zeqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bat" {...props}></Icon>
