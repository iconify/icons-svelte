<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szgr5abtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szgr5abtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:face-explode-solid" {...props}></Icon>
