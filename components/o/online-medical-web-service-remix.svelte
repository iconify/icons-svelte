<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3pejtb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e3pejtb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:online-medical-web-service-remix" {...props}></Icon>
