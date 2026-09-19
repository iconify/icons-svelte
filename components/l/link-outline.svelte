<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k176_rbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k176_rbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:link-outline" {...props}></Icon>
