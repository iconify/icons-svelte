<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu62vb9be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu62vb9be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:clinic" {...props}></Icon>
