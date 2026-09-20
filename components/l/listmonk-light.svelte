<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2bhwcb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2bhwcb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listmonk-light" {...props}></Icon>
