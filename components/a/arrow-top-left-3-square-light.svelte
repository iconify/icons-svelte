<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl4i9x41k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4i9x41k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-3-square-light" {...props}></Icon>
