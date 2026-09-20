<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhq1y23qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qhq1y23qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:blur-filled" {...props}></Icon>
