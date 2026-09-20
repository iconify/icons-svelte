<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9qd5__9z.css';
import '../../css/p/p93a1fbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9qd5__9z"/><path class="p93a1fbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favourite-bold" {...props}></Icon>
