<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etts-obta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="etts-obta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mosquito" {...props}></Icon>
