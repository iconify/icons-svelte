<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d17dszf8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="d17dszf8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:delete" {...props}></Icon>
