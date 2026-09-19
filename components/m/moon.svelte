<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keqwgvb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="keqwgvb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:moon" {...props}></Icon>
