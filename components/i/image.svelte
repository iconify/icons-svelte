<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzljxcb6h.css';
import '../../css/l/lugjjbc-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzljxcb6h"/><path class="lugjjbc-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:image" {...props}></Icon>
