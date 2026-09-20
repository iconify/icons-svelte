<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmdco-tds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmdco-tds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-open-check" {...props}></Icon>
