<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v76gq-blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v76gq-blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-search-01" {...props}></Icon>
