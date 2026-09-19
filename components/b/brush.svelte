<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms7r-wb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms7r-wb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:brush" {...props}></Icon>
