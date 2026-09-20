<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlz0qlb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nlz0qlb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:customer-support-1-remix" {...props}></Icon>
