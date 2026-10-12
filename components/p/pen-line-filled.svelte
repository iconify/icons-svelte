<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfmj2etah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfmj2etah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pen-line-filled" {...props}></Icon>
