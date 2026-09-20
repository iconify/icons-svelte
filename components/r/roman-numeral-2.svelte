<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhthw0hea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhthw0hea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:roman-numeral-2" {...props}></Icon>
