<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl51kobzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl51kobzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:quote-single-fill" {...props}></Icon>
