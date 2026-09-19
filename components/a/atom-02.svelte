<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i_ocz4bfi.css';
import '../../css/k/kbkcdjbmr.css';
import '../../css/v/v2jut0b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path clip-rule="evenodd" class="i_ocz4bfi"/><path clip-rule="evenodd" class="kbkcdjbmr"/><path class="v2jut0b8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:atom-02" {...props}></Icon>
