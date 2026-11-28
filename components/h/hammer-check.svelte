<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfv202b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfv202b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hammer-check" {...props}></Icon>
