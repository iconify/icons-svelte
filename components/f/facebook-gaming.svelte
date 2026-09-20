<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc4uod5nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc4uod5nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:facebook-gaming" {...props}></Icon>
