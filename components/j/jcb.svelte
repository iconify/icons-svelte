<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqi5l08ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqi5l08ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jcb" {...props}></Icon>
