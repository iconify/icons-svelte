<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk6mc0bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk6mc0bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-right-bold" {...props}></Icon>
