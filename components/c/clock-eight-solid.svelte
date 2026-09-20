<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfzc1ffoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzc1ffoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-eight-solid" {...props}></Icon>
