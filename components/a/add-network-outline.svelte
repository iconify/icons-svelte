<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-7suk1ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-7suk1ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:add-network-outline" {...props}></Icon>
