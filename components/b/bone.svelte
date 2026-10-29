<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwx6u199w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwx6u199w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:bone" {...props}></Icon>
