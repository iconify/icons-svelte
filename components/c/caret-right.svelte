<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldhud7ziz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldhud7ziz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:caret-right" {...props}></Icon>
