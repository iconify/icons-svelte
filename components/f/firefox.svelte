<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ovopb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="z5ovopb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:firefox" {...props}></Icon>
