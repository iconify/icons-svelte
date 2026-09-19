<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxmemdtnq.css';
import '../../css/a/az7opmutd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmemdtnq"/><path class="az7opmutd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:mobile-3" {...props}></Icon>
