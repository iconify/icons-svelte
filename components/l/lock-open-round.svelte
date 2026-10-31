<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n19-y4f_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n19-y4f_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-open-round" {...props}></Icon>
