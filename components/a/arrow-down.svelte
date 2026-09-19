<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ood-b4bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ood-b4bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-down" {...props}></Icon>
