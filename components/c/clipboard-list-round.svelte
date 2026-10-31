<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngw559-hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngw559-hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-list-round" {...props}></Icon>
