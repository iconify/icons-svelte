<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_h4tsf_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f_h4tsf_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:product-hunt" {...props}></Icon>
