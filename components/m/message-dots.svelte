<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w__oz7bxg.css';
import '../../css/k/k_lqyobox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w__oz7bxg"/><path class="k_lqyobox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:message-dots" {...props}></Icon>
