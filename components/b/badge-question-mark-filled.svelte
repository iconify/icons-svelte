<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_gkf5rlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_gkf5rlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-question-mark-filled" {...props}></Icon>
