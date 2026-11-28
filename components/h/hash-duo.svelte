<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8dorub4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8dorub4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hash-duo" {...props}></Icon>
