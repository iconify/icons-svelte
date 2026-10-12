<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld-ldz2zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-ldz2zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fast-forward-filled" {...props}></Icon>
