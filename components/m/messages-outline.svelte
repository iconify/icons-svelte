<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lweg38u7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lweg38u7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:messages-outline" {...props}></Icon>
