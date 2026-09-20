<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkzbi_b2t.css';
import '../../css/k/ki5l85g2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkzbi_b2t"/><path class="ki5l85g2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:check-square" {...props}></Icon>
