<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crq6d2swy.css';
import '../../css/z/z0_ytrr1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crq6d2swy"/><path class="z0_ytrr1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dog" {...props}></Icon>
