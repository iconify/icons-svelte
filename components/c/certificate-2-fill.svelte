<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx5-cytsq.css';
import '../../css/f/fp4ye0bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx5-cytsq"/><path class="fp4ye0bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:certificate-2-fill" {...props}></Icon>
