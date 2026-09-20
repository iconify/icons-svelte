<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on5qrlw_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on5qrlw_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-ted" {...props}></Icon>
