<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0s8dnbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="b0s8dnbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:menu-hamburger-1" {...props}></Icon>
