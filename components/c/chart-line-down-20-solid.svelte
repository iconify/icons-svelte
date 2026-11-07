<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_cpzsbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z_cpzsbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chart-line-down-20-solid" {...props}></Icon>
