<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlflq_dgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jlflq_dgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onedev-dark" {...props}></Icon>
