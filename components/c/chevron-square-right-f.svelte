<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay6ivfsaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ay6ivfsaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-square-right-f" {...props}></Icon>
