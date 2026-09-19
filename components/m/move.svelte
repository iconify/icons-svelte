<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqh5nbc3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqh5nbc3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:move" {...props}></Icon>
