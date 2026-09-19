<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nygz9v8nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nygz9v8nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-datastax" {...props}></Icon>
