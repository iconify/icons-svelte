<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5kq2yfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ke5kq2yfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:gem" {...props}></Icon>
