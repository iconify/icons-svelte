<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do16onk9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="do16onk9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-2-fill" {...props}></Icon>
