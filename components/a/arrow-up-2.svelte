<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2yc4bcau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2yc4bcau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-2" {...props}></Icon>
