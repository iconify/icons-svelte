<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2vu9_i2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s2vu9_i2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:parallelogram" {...props}></Icon>
