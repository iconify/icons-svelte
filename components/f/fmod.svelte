<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke73_tt5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke73_tt5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fmod" {...props}></Icon>
