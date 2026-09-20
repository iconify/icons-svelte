<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7yg9o87o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="r7yg9o87o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:plus-circle-f" {...props}></Icon>
