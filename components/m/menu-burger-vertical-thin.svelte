<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thsd4275x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thsd4275x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-vertical-thin" {...props}></Icon>
