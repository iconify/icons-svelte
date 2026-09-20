<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrasqh2gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrasqh2gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-e-octagon-solid" {...props}></Icon>
