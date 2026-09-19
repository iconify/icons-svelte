<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zezrunbvz.css';
import '../../css/i/i55evib8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zezrunbvz"/><path class="i55evib8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:refresh-sharp" {...props}></Icon>
