<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpsaa-b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpsaa-b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:paper-roll-2" {...props}></Icon>
