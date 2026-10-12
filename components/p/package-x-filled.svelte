<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj7aqqr_k.css';
import '../../css/x/xomsf6buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj7aqqr_k"/><path class="xomsf6buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-x-filled" {...props}></Icon>
