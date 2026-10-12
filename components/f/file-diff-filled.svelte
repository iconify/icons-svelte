<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrsb5o73i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrsb5o73i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-diff-filled" {...props}></Icon>
