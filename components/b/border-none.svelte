<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p94whofhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p94whofhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:border-none" {...props}></Icon>
