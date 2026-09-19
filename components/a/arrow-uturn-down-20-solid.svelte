<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khi1fr4mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="khi1fr4mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-down-20-solid" {...props}></Icon>
