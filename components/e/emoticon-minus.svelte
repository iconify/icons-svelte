<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz0hucbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz0hucbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-minus" {...props}></Icon>
