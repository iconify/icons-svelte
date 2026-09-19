<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_goi9h2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_goi9h2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-up-20-solid" {...props}></Icon>
