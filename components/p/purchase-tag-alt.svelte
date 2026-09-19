<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-c1osbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-c1osbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:purchase-tag-alt" {...props}></Icon>
