<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ade6m6cnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ade6m6cnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:parasol-filled" {...props}></Icon>
