<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d66mew_du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d66mew_du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:down-arrow-alt" {...props}></Icon>
