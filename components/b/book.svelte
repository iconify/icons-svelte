<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiqk-gcqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiqk-gcqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book" {...props}></Icon>
