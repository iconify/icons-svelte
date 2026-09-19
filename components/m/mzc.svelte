<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjvcafbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vjvcafbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mzc" {...props}></Icon>
