<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjchw2bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjchw2bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-mic" {...props}></Icon>
