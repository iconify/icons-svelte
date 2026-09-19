<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe7lh5wmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pe7lh5wmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:page-list-solid" {...props}></Icon>
