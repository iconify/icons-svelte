<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx4oct3hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx4oct3hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:multiply-square-fill" {...props}></Icon>
