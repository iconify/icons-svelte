<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxe6m81df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxe6m81df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flip-horizontal" {...props}></Icon>
