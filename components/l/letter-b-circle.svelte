<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfnh49bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfnh49bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-b-circle" {...props}></Icon>
