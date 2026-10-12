<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4a0pfb5b.css';
import '../../css/y/y_elplb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4a0pfb5b"/><path clip-rule="evenodd" class="y_elplb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brick-wall-shield-filled" {...props}></Icon>
