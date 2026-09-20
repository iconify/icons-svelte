<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/filr94yjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="filr94yjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:reception-bell-solid" {...props}></Icon>
