<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_4soybfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_4soybfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:expand-outline" {...props}></Icon>
