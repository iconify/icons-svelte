<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmj_96ose.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="nmj_96ose"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:keyboard" {...props}></Icon>
