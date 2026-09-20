<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh3kbwobr.css';
import '../../css/q/q7cll_b2k.css';
import '../../css/c/cpbja35_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3kbwobr"/><path clip-rule="evenodd" class="q7cll_b2k"/><path clip-rule="evenodd" class="cpbja35_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-date" {...props}></Icon>
