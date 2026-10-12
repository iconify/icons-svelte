<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x72_jn4yw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x72_jn4yw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-horizontal-filled" {...props}></Icon>
