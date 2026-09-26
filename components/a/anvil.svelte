<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0qq-b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zg0qq-b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:anvil" {...props}></Icon>
