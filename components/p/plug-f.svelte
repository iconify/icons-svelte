<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfbmbcpyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-1.5};
const content = `<path class="dfbmbcpyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:plug-f" {...props}></Icon>
