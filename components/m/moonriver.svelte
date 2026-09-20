<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro-y-y6ov.css';
import '../../css/w/wavzocqjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-y-y6ov"/><path class="wavzocqjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:moonriver" {...props}></Icon>
