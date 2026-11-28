<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvzm9-bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzm9-bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rabbit" {...props}></Icon>
