<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od2q7ebbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od2q7ebbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-pencil" {...props}></Icon>
