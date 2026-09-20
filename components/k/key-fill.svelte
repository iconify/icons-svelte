<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy5k3mbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy5k3mbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:key-fill" {...props}></Icon>
