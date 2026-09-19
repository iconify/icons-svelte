<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2dtwdbdi.css';
import '../../css/s/sec7i9buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2dtwdbdi"/><path class="sec7i9buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-man" {...props}></Icon>
