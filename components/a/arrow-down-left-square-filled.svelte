<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu56-l6qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xu56-l6qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-left-square-filled" {...props}></Icon>
