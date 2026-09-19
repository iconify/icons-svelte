<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0tnk7uws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c0tnk7uws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-right-fill-12" {...props}></Icon>
