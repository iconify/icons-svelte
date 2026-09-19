<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvxc6dbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvxc6dbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pointing-right-04" {...props}></Icon>
