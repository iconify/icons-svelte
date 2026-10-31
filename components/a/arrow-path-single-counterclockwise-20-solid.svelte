<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16cutbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k16cutbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise-20-solid" {...props}></Icon>
