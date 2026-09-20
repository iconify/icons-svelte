<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd4rf3b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="bd4rf3b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mountain-f" {...props}></Icon>
