<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlvjc1tia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hlvjc1tia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bze" {...props}></Icon>
