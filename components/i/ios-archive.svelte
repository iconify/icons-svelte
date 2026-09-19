<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzlocfotl.css';
import '../../css/k/kx9-9-b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzlocfotl"/><path class="kx9-9-b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-archive" {...props}></Icon>
