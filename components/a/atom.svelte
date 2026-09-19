<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh1l9-vtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":898,"height":1024};
const content = `<path class="dh1l9-vtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:atom" {...props}></Icon>
