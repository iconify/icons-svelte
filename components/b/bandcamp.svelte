<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9oq_dbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9oq_dbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:bandcamp" {...props}></Icon>
