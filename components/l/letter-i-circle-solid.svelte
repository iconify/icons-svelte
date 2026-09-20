<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osh5ijbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osh5ijbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-circle-solid" {...props}></Icon>
