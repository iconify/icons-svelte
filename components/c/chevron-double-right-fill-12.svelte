<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnzxjem_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nnzxjem_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-right-fill-12" {...props}></Icon>
