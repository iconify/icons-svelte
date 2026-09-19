<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tju_bxjlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tju_bxjlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-forward-circle-sharp" {...props}></Icon>
