<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tabi2-kal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tabi2-kal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-thin" {...props}></Icon>
