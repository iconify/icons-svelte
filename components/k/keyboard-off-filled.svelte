<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aynqz1gse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aynqz1gse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:keyboard-off-filled" {...props}></Icon>
