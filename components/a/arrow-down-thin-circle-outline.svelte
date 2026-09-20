<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z85omn0_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z85omn0_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-thin-circle-outline" {...props}></Icon>
