<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d43s5euap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d43s5euap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-question-mark-filled" {...props}></Icon>
