<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhzo-tp2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xhzo-tp2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headphones-20-solid" {...props}></Icon>
