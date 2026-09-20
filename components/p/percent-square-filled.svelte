<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1maur2rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1maur2rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:percent-square-filled" {...props}></Icon>
