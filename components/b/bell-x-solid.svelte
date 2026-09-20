<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn46jyyfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn46jyyfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bell-x-solid" {...props}></Icon>
