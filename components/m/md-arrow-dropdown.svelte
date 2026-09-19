<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt64rj3ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt64rj3ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-dropdown" {...props}></Icon>
