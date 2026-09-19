<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q199cwabh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q199cwabh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:jar-wheat-solid" {...props}></Icon>
