<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5gmkxb2i.css';
import '../../css/m/m_zeiqb1i.css';
import '../../css/b/bqm3pcmff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z5gmkxb2i"/><path class="m_zeiqb1i"/><path class="bqm3pcmff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:parameter" {...props}></Icon>
