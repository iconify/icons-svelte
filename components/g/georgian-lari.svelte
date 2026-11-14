<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3gb_ebil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3gb_ebil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:georgian-lari" {...props}></Icon>
