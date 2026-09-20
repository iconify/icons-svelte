<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3e34pbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3e34pbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:backpack-off" {...props}></Icon>
