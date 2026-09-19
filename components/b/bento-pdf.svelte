<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsxfjy2lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsxfjy2lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bento-pdf" {...props}></Icon>
