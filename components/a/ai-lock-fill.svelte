<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ost-0qr-b.css';
import '../../css/r/r5tlw_31c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ost-0qr-b"/><path clip-rule="evenodd" class="r5tlw_31c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-lock-fill" {...props}></Icon>
