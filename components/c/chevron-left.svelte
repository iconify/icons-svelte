<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjs0mbcre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yjs0mbcre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:chevron-left" {...props}></Icon>
