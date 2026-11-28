<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k124hfb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k124hfb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-5-duo" {...props}></Icon>
