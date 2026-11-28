<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cw6wvybnf.css';
import '../../css/n/nlss26bwx.css';
import '../../css/r/rb1ysv58h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cw6wvybnf"/><path class="nlss26bwx"/><path class="rb1ysv58h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:mail-send" {...props}></Icon>
