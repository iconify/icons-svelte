<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afj-pcbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afj-pcbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gmail" {...props}></Icon>
