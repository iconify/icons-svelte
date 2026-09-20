<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo47_w.css';
import '../../css/s/so-from-12.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo47_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:close" {...props}></Icon>
