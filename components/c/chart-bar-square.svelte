<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7103_b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w7103_b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-bar-square" {...props}></Icon>
