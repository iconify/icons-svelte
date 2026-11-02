<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by4_c8chv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by4_c8chv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mirror-fill" {...props}></Icon>
