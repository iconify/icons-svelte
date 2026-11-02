<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lilp8103o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lilp8103o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-space-between-fill" {...props}></Icon>
