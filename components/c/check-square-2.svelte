<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du_6b3bct.css';
import '../../css/a/apxnxjkhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du_6b3bct"/><path class="apxnxjkhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:check-square-2" {...props}></Icon>
