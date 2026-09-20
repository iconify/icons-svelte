<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4lfpob_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4lfpob_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:mail-open" {...props}></Icon>
