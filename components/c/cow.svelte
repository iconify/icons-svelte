<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1_vr9bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="s1_vr9bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cow" {...props}></Icon>
