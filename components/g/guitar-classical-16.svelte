<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1cd9e3yd.css';
import '../../css/l/lsqebab9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b1cd9e3yd"/><path class="lsqebab9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-classical-16" {...props}></Icon>
