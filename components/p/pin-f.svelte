<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvibj51bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="pvibj51bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pin-f" {...props}></Icon>
