<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_cqrlblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q_cqrlblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-down-20-solid" {...props}></Icon>
