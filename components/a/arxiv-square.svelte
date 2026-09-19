<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvbzddb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tvbzddb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:arxiv-square" {...props}></Icon>
