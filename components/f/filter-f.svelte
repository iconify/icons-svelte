<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9nylr9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="co9nylr9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:filter-f" {...props}></Icon>
