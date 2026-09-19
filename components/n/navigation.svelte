<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm2nnvbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm2nnvbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigation" {...props}></Icon>
