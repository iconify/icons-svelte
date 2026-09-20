<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myyxy-blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myyxy-blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-move-up-filled" {...props}></Icon>
