<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfm7feroz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfm7feroz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-open-filled" {...props}></Icon>
