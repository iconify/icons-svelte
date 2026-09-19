<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l409kybhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l409kybhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-up-6-circle-fill" {...props}></Icon>
