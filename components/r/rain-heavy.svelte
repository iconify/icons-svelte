<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld2zemtmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld2zemtmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:rain-heavy" {...props}></Icon>
