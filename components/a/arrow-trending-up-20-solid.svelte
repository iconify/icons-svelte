<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxiassbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nxiassbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-trending-up-20-solid" {...props}></Icon>
