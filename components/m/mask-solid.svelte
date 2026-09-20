<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ootzgdtft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ootzgdtft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:mask-solid" {...props}></Icon>
