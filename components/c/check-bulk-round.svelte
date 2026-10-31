<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi26zpr3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi26zpr3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:check-bulk-round" {...props}></Icon>
