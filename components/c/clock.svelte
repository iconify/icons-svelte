<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_qro1bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="n_qro1bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:clock" {...props}></Icon>
