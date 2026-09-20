<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgfyvbb5e.css';
import '../../css/u/ud8i2ab-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zgfyvbb5e"/><path class="ud8i2ab-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:reply-all" {...props}></Icon>
