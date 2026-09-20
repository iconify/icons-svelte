<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20sm2b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l20sm2b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cart-add-solid" {...props}></Icon>
