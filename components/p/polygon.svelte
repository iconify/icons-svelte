<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps-6-ibio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps-6-ibio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:polygon" {...props}></Icon>
