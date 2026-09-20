<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtp6h5bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtp6h5bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lights" {...props}></Icon>
