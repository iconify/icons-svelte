<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7u9rlhtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l7u9rlhtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-apps" {...props}></Icon>
