<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-r1g3cny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-r1g3cny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:font-size" {...props}></Icon>
