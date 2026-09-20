<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8zgv-btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8zgv-btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-remove" {...props}></Icon>
