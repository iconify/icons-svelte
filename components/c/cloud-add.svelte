<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdmoaebxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdmoaebxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-add" {...props}></Icon>
