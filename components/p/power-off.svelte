<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by-tp_ohk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by-tp_ohk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:power-off" {...props}></Icon>
