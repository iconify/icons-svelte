<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnlc4esmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnlc4esmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:container-clock" {...props}></Icon>
