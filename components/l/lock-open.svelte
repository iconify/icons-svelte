<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lff1pxbum.css';
import '../../css/o/ob4ovv27x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lff1pxbum"/><path class="ob4ovv27x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:lock-open" {...props}></Icon>
