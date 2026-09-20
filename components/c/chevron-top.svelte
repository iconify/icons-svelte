<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb6fqubbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eb6fqubbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:chevron-top" {...props}></Icon>
