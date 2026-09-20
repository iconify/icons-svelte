<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoe8grbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoe8grbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:braces-fill" {...props}></Icon>
