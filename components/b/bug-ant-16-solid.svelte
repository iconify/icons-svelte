<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sey0_cb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sey0_cb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bug-ant-16-solid" {...props}></Icon>
