<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpsjg6mpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mpsjg6mpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-right-up-20-solid" {...props}></Icon>
