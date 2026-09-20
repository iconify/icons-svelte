<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03c0fb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s03c0fb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:affiliatetheme" {...props}></Icon>
