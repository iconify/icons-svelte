<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezodczb5s.css';
import '../../css/s/s4hxl1lwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezodczb5s"/><path clip-rule="evenodd" class="s4hxl1lwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-indesign-solid" {...props}></Icon>
