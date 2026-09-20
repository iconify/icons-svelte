<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3qg2sb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3qg2sb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-dashed" {...props}></Icon>
