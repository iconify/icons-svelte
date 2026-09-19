<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0cnftqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wu0cnftqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-postgresql" {...props}></Icon>
