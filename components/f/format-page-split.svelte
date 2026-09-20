<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbggd5yiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbggd5yiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-page-split" {...props}></Icon>
