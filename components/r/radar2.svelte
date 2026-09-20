<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cro2snina.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cro2snina"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar2" {...props}></Icon>
