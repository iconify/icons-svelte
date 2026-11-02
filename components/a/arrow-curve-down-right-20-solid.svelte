<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv1o4ubmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mv1o4ubmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-right-20-solid" {...props}></Icon>
