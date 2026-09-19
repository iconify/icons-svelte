<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ustwq2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d6ustwq2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:question-filled" {...props}></Icon>
