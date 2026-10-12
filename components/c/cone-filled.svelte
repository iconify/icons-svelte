<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz2i4y3pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz2i4y3pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cone-filled" {...props}></Icon>
