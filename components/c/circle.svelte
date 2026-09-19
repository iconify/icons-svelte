<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ratgbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d2ratgbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle" {...props}></Icon>
