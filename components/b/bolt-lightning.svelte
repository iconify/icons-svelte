<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj9z2dhot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="bj9z2dhot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bolt-lightning" {...props}></Icon>
