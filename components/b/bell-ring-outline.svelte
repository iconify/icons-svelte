<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al0-lwb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al0-lwb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bell-ring-outline" {...props}></Icon>
