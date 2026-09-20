<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by5sttbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by5sttbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:apple-filled" {...props}></Icon>
