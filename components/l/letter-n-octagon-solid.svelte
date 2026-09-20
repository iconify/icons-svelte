<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvoio1bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvoio1bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-n-octagon-solid" {...props}></Icon>
