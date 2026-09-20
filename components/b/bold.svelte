<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo-m8hbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-m8hbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bold" {...props}></Icon>
