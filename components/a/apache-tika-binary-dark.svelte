<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0vdxm-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lx0vdxm-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tika-binary-dark" {...props}></Icon>
