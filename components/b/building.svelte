<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlhh1586r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qlhh1586r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:building" {...props}></Icon>
