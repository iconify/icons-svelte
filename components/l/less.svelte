<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo6s7v_7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="eo6s7v_7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:less" {...props}></Icon>
