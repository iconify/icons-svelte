<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px09f3oic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="px09f3oic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-slash-20-solid" {...props}></Icon>
