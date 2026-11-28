<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxv7o_b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxv7o_b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:knife" {...props}></Icon>
