<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv53gcbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv53gcbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:palo-alto-networks" {...props}></Icon>
