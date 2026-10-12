<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zptjmc6mm.css';
import '../../css/v/vb6m8wb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zptjmc6mm"/><path class="vb6m8wb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-x-filled" {...props}></Icon>
