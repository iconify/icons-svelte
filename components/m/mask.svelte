<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow894ob8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6.5};
const content = `<path class="ow894ob8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mask" {...props}></Icon>
