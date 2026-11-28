<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if3j1ybfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if3j1ybfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:armchair-solid" {...props}></Icon>
