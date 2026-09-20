<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j05mr2p2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j05mr2p2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:floppy-disk-solid" {...props}></Icon>
