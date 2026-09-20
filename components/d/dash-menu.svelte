<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnx55hbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnx55hbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dash-menu" {...props}></Icon>
