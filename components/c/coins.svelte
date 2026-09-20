<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lda6pabva.css';
import '../../css/t/ttouprbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lda6pabva"/><path class="ttouprbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:coins" {...props}></Icon>
