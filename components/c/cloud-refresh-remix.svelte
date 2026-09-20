<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2cojm2_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v2cojm2_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-refresh-remix" {...props}></Icon>
