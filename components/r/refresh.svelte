<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1np3qbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="h1np3qbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:refresh" {...props}></Icon>
