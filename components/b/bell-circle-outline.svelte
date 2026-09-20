<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-xku8bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-xku8bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-circle-outline" {...props}></Icon>
