<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/talrrz3nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="talrrz3nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-to-right" {...props}></Icon>
