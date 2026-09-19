<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcz4umbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz4umbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevron-last" {...props}></Icon>
