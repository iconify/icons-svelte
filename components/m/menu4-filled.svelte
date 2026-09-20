<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncoo9jbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncoo9jbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:menu4-filled" {...props}></Icon>
