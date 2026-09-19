<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ns-1bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ns-1bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb" {...props}></Icon>
