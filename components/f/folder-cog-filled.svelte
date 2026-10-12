<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auxij4h6f.css';
import '../../css/k/k9isiyb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="auxij4h6f"/><path class="k9isiyb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-cog-filled" {...props}></Icon>
