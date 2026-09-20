<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckv1mmfoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckv1mmfoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:more-square3-filled" {...props}></Icon>
