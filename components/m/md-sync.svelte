<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht297tb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht297tb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-sync" {...props}></Icon>
