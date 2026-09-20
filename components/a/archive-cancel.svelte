<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myf0cab_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myf0cab_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-cancel" {...props}></Icon>
