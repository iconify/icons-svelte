<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlyoxob2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlyoxob2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bluesound" {...props}></Icon>
