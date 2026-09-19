<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmelaowtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmelaowtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:briefcase-alt" {...props}></Icon>
