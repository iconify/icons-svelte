<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaj8_bb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaj8_bb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-telegram" {...props}></Icon>
