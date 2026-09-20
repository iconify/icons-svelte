<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsh1hrhbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsh1hrhbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-square-solid" {...props}></Icon>
