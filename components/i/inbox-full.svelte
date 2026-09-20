<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42c7bcyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k42c7bcyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:inbox-full" {...props}></Icon>
