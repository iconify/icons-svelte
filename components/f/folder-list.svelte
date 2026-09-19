<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy0ae6bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sy0ae6bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:folder-list" {...props}></Icon>
