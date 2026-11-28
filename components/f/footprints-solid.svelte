<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht_9xhb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht_9xhb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:footprints-solid" {...props}></Icon>
