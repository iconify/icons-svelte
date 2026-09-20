<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3qn_6bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="o3qn_6bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pound" {...props}></Icon>
