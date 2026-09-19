<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfk143v7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfk143v7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-4-light" {...props}></Icon>
