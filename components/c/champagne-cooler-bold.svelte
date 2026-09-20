<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo5h1rzkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo5h1rzkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:champagne-cooler-bold" {...props}></Icon>
