<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk6ynbs5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk6ynbs5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:inbox-check-solid" {...props}></Icon>
