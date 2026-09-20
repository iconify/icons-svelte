<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv49c2bhl.css';
import '../../css/s/sw90srnhq.css';
import '../../css/i/iebf_nbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv49c2bhl"/><path class="sw90srnhq"/><path class="iebf_nbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:counter-2-line" {...props}></Icon>
