<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_i7i9-5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a_i7i9-5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:lasso" {...props}></Icon>
