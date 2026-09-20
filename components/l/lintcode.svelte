<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2mqnrb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2mqnrb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lintcode" {...props}></Icon>
