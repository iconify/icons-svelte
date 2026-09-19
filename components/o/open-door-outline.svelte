<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyvh2j2cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyvh2j2cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:open-door-outline" {...props}></Icon>
