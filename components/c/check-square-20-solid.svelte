<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpsumob8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hpsumob8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-square-20-solid" {...props}></Icon>
