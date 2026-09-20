<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsxw9ekqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qsxw9ekqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dizzy" {...props}></Icon>
