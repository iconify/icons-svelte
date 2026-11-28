<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3x3jbc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3x3jbc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:apple-check" {...props}></Icon>
