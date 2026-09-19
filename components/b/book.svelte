<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdhn56ehw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hdhn56ehw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:book" {...props}></Icon>
