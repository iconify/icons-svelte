<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9uds8nda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9uds8nda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-left-07" {...props}></Icon>
