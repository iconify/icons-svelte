<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3m55ehci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3m55ehci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrows-up-from-line" {...props}></Icon>
