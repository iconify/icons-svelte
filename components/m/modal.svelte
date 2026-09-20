<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eftq4hb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eftq4hb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:modal" {...props}></Icon>
