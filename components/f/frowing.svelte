<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb-i_hbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb-i_hbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:frowing" {...props}></Icon>
