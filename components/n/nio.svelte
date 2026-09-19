<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9976bbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z9976bbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nio" {...props}></Icon>
