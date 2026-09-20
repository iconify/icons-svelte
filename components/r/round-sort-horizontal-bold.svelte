<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdqm6cbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdqm6cbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-sort-horizontal-bold" {...props}></Icon>
