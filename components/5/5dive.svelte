<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt2dpnbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt2dpnbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:5dive" {...props}></Icon>
