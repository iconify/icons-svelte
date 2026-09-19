<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bas7btrby.css';
import '../../css/x/x7m723b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bas7btrby"/><path class="x7m723b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-speedometer-outline" {...props}></Icon>
