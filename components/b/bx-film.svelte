<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8zsvzb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8zsvzb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-film" {...props}></Icon>
