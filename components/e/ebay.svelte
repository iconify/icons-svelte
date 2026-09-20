<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bquigi8rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-7.5};
const content = `<path class="bquigi8rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:ebay" {...props}></Icon>
