<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brc0qgbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brc0qgbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-1-sharp-fill" {...props}></Icon>
