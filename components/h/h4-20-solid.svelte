<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6vw2s0ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k6vw2s0ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h4-20-solid" {...props}></Icon>
