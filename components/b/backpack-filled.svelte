<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2huzkbqd.css';
import '../../css/u/uijt22b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2huzkbqd"/><path class="uijt22b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:backpack-filled" {...props}></Icon>
