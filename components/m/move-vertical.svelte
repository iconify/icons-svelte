<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqcrhnbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqcrhnbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:move-vertical" {...props}></Icon>
