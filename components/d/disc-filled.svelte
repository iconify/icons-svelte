<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmb-0o7z.css';
import '../../css/c/c3vmx5bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmb-0o7z"/><path clip-rule="evenodd" class="c3vmx5bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:disc-filled" {...props}></Icon>
