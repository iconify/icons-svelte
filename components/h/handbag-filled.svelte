<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8k8jpgoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8k8jpgoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:handbag-filled" {...props}></Icon>
