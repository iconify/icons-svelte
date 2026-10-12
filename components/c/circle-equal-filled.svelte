<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmps9kb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lmps9kb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-equal-filled" {...props}></Icon>
