<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez6-9mb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez6-9mb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-page-break" {...props}></Icon>
