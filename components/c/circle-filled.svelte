<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s56bahb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s56bahb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-filled" {...props}></Icon>
