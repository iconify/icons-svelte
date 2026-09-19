<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-eam-cmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-eam-cmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bread-slice-solid" {...props}></Icon>
