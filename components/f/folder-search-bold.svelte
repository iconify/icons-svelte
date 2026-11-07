<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5dxyelor.css';
import '../../css/f/f03p8tb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5dxyelor"/><path clip-rule="evenodd" class="f03p8tb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-search-bold" {...props}></Icon>
