<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ondqgb3it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ondqgb3it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mln" {...props}></Icon>
