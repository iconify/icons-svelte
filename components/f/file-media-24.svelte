<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ror_0p-9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ror_0p-9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-media-24" {...props}></Icon>
