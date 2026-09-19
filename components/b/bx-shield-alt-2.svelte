<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uay35lbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uay35lbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-shield-alt-2" {...props}></Icon>
