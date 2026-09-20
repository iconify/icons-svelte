<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1pz5ebrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pz5ebrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alarm-fill" {...props}></Icon>
