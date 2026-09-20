<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be2pofbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be2pofbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-variant" {...props}></Icon>
