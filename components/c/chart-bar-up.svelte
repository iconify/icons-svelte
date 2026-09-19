<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh2x5dbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh2x5dbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-up" {...props}></Icon>
