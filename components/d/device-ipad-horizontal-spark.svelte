<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx9p37-xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx9p37-xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-spark" {...props}></Icon>
