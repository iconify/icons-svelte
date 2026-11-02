<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okxd8xsdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okxd8xsdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-alert-fill" {...props}></Icon>
