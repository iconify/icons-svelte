<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyde7_dhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nyde7_dhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:gift" {...props}></Icon>
