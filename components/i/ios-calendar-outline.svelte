<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw0ekm9xl.css';
import '../../css/n/n_y4z0b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xw0ekm9xl"/><path class="n_y4z0b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-calendar-outline" {...props}></Icon>
