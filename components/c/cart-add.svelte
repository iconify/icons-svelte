<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t12f6_cmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t12f6_cmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cart-add" {...props}></Icon>
