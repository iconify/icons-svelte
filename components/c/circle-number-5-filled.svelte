<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggwovzb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggwovzb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-number-5-filled" {...props}></Icon>
