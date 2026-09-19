<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l00k7ibfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l00k7ibfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-cloud-02" {...props}></Icon>
