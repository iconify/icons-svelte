<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2d9kktld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2d9kktld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-1-duo" {...props}></Icon>
