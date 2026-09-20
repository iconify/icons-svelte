<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ockkzxa_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ockkzxa_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flag-4-filled" {...props}></Icon>
