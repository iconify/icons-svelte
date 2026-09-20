<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocb0xlwdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocb0xlwdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:phone-find-fill" {...props}></Icon>
