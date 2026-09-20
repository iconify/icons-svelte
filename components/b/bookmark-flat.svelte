<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0778o7nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f0778o7nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:bookmark-flat" {...props}></Icon>
