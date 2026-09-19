<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegzprb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oegzprb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:plus" {...props}></Icon>
