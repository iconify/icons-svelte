<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6g2-ok-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6g2-ok-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:heart" {...props}></Icon>
