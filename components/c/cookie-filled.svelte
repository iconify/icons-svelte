<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz3abnbbb.css';
import '../../css/y/y1iswdb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gz3abnbbb"/><path class="y1iswdb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cookie-filled" {...props}></Icon>
