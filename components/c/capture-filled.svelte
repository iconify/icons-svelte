<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aow3f85ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aow3f85ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:capture-filled" {...props}></Icon>
