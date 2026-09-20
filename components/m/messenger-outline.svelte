<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iak_x3heq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iak_x3heq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:messenger-outline" {...props}></Icon>
