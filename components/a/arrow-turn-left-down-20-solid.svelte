<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7x7srsks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k7x7srsks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-down-20-solid" {...props}></Icon>
