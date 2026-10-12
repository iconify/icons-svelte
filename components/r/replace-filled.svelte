<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxe47ha6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxe47ha6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:replace-filled" {...props}></Icon>
