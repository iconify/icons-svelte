<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4jf94ekx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4jf94ekx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:arrow-left" {...props}></Icon>
