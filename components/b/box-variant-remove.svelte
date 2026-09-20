<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch-7vfbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch-7vfbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-variant-remove" {...props}></Icon>
