<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5crthepf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5crthepf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:attach-2-outline" {...props}></Icon>
