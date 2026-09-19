<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu-65jynz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu-65jynz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-2-bold" {...props}></Icon>
