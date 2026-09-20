<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz41l0bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz41l0bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-badge-down-filled" {...props}></Icon>
