<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta6dmmbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta6dmmbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:abstract" {...props}></Icon>
