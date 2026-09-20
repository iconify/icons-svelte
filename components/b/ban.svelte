<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2zw_0hnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="s2zw_0hnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ban" {...props}></Icon>
