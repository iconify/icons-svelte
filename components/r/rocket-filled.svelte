<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w26gjsv3k.css';
import '../../css/j/jxs7zfb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w26gjsv3k"/><path class="jxs7zfb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:rocket-filled" {...props}></Icon>
