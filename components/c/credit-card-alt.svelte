<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0k05-oyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0k05-oyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:credit-card-alt" {...props}></Icon>
