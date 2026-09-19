<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhf4zz28w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhf4zz28w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-list" {...props}></Icon>
