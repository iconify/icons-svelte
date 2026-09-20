<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlmi74dop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mlmi74dop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-to-top-left-filled" {...props}></Icon>
