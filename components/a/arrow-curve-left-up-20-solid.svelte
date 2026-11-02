<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_owd-wra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_owd-wra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-up-20-solid" {...props}></Icon>
