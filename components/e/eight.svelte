<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz_a4acti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zz_a4acti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eight" {...props}></Icon>
