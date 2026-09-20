<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8ci34jwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8ci34jwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:open-ai" {...props}></Icon>
