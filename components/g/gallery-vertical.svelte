<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia-obpbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia-obpbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gallery-vertical" {...props}></Icon>
