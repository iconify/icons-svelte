<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7c9xsbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7c9xsbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bandage-filled" {...props}></Icon>
