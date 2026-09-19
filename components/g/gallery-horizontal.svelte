<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w025-gj6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w025-gj6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-horizontal" {...props}></Icon>
