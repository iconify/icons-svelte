<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjyzoybne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjyzoybne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:notebook-text-filled" {...props}></Icon>
