<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdf1evbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdf1evbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:commento-dark" {...props}></Icon>
