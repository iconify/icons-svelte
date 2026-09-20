<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtwzzdbkp.css';
import '../../css/r/rri86bcuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtwzzdbkp"/><path class="rri86bcuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cart-minus" {...props}></Icon>
