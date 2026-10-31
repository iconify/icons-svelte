<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj7aydm1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uj7aydm1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass-20-solid" {...props}></Icon>
