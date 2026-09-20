<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qztjxpaci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qztjxpaci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-minimalistic-outline" {...props}></Icon>
