<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nolju0brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nolju0brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-dashed" {...props}></Icon>
