<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv9089pvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv9089pvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alltrails" {...props}></Icon>
