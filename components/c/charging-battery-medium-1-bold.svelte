<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjtzypblm.css';
import '../../css/l/lg8uylb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjtzypblm"/><path class="lg8uylb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:charging-battery-medium-1-bold" {...props}></Icon>
