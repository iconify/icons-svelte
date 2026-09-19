<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywx5vibya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ywx5vibya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:compare-uneven" {...props}></Icon>
