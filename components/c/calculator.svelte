<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4afgeb-d.css';
import '../../css/v/v1z4zvbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4afgeb-d"/><path class="v1z4zvbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:calculator" {...props}></Icon>
