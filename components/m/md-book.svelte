<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zshchnb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zshchnb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-book" {...props}></Icon>
