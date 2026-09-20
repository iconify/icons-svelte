<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oocirobjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oocirobjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:box-3-fill" {...props}></Icon>
