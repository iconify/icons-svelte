<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p70oy3bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p70oy3bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:pentagon-fill" {...props}></Icon>
