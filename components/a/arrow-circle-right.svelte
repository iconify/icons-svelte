<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fealj4bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fealj4bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-circle-right" {...props}></Icon>
