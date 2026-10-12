<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z59x0ffla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z59x0ffla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-question-mark-filled" {...props}></Icon>
