<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3dte_aui.css';
import '../../css/p/p51mxvbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dte_aui"/><path class="p51mxvbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ctr" {...props}></Icon>
