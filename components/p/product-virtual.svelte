<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc8p4nbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8p4nbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:product-virtual" {...props}></Icon>
