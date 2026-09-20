<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zctq2zbbr.css';
import '../../css/z/zoj-nnnyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zctq2zbbr"/><path class="zoj-nnnyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mntl" {...props}></Icon>
