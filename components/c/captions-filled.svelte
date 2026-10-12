<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajg2szb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ajg2szb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:captions-filled" {...props}></Icon>
