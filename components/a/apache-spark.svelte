<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh3su9blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sh3su9blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:apache-spark" {...props}></Icon>
