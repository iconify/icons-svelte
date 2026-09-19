<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia86285af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia86285af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:backward-step-outline" {...props}></Icon>
