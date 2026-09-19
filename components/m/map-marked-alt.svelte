<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1p808bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="b1p808bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:map-marked-alt" {...props}></Icon>
