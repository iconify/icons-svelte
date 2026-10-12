<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qams0c-7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qams0c-7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-vertical-justify-start-filled" {...props}></Icon>
