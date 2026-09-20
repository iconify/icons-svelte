<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwy_bs32g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kwy_bs32g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-outline-left" {...props}></Icon>
