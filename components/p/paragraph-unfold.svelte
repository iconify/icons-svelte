<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzky99b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gzky99b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:paragraph-unfold" {...props}></Icon>
