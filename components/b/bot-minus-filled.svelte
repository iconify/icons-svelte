<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdj0_9ype.css';
import '../../css/g/ge98ujwjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdj0_9ype"/><path class="ge98ujwjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bot-minus-filled" {...props}></Icon>
