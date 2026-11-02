<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovicm5b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovicm5b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-x-fill" {...props}></Icon>
