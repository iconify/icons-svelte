<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xezfrunop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xezfrunop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:building-a-fill" {...props}></Icon>
