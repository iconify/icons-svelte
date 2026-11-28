<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hav6w5euk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hav6w5euk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-down" {...props}></Icon>
