<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1bw8ugd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da1bw8ugd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-2-solid" {...props}></Icon>
