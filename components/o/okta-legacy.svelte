<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgbl27bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgbl27bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:okta-legacy" {...props}></Icon>
