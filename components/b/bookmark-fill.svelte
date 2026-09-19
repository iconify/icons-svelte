<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6-now6rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6-now6rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bookmark-fill" {...props}></Icon>
