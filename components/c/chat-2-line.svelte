<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjec12bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjec12bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-2-line" {...props}></Icon>
