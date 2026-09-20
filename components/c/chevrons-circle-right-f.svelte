<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlxh3ub9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="dlxh3ub9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-right-f" {...props}></Icon>
