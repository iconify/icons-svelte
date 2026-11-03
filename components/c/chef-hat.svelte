<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohuob9vol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohuob9vol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chef-hat" {...props}></Icon>
