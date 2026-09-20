<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hplk8z63w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hplk8z63w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-lamp-torchiere-outline" {...props}></Icon>
