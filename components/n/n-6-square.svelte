<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb865obzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="nb865obzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:n-6-square" {...props}></Icon>
