<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4br_ebme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4br_ebme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-2-fill" {...props}></Icon>
