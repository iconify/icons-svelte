<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaodx6v3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaodx6v3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-x" {...props}></Icon>
