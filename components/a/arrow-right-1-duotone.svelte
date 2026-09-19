<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggn_p2b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggn_p2b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-1-duotone" {...props}></Icon>
