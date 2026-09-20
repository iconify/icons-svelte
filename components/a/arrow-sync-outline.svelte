<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7q0h15ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7q0h15ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-sync-outline" {...props}></Icon>
