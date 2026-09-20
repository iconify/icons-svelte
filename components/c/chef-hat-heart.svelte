<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp97wsb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rp97wsb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chef-hat-heart" {...props}></Icon>
