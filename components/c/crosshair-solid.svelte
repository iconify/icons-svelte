<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6cs2hb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p6cs2hb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crosshair-solid" {...props}></Icon>
