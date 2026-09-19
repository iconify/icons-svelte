<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8x-vccbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="d8x-vccbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:idea" {...props}></Icon>
