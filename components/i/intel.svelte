<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovoughbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovoughbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:intel" {...props}></Icon>
