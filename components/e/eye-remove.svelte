<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2cm2bcau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2cm2bcau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-remove" {...props}></Icon>
