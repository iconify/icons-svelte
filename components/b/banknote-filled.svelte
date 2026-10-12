<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmb-0o7z.css';
import '../../css/h/hbrz9e2ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmb-0o7z"/><path clip-rule="evenodd" class="hbrz9e2ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-filled" {...props}></Icon>
