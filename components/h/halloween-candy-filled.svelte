<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xptlr6bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xptlr6bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-candy-filled" {...props}></Icon>
