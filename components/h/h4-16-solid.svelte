<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei424mv-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ei424mv-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h4-16-solid" {...props}></Icon>
