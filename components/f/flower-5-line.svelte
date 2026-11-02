<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo3w5zbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo3w5zbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-5-line" {...props}></Icon>
