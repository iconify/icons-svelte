<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai0oe79so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai0oe79so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:ellipsis-circle" {...props}></Icon>
