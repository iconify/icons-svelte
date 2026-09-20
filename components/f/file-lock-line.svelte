<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8lpyt6bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8lpyt6bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-lock-line" {...props}></Icon>
