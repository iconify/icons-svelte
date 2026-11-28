<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8d5wzodb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8d5wzodb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coffee-check" {...props}></Icon>
