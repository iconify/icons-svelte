<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djj8e4c7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":688,"height":717};
const content = `<path class="djj8e4c7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:light" {...props}></Icon>
