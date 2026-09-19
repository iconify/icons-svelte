<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p49r76-de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p49r76-de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-0-light" {...props}></Icon>
