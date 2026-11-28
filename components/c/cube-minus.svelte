<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsoh2nbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsoh2nbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cube-minus" {...props}></Icon>
