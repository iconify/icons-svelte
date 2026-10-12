<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvnvmob9i.css';
import '../../css/u/u769r-biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnvmob9i"/><path clip-rule="evenodd" class="u769r-biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-off-filled" {...props}></Icon>
