<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krjlfzbvg.css';
import '../../css/z/zgjqvdbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="krjlfzbvg"/><path class="zgjqvdbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openuem-dark" {...props}></Icon>
