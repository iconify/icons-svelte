<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md1w59b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md1w59b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ghost-filled" {...props}></Icon>
