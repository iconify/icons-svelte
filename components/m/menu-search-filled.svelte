<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1s7dnb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1s7dnb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:menu-search-filled" {...props}></Icon>
