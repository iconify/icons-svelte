<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz12o2b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz12o2b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:island" {...props}></Icon>
