<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxhoww8eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxhoww8eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:face-angry" {...props}></Icon>
