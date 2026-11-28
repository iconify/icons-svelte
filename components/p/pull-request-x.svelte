<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t12c4qa7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t12c4qa7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pull-request-x" {...props}></Icon>
