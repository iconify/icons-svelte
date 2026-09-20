<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my3unjbkn.css';
import '../../css/y/y8ai33b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="my3unjbkn"/><path class="y8ai33b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:cash" {...props}></Icon>
