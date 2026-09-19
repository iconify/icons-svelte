<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1jm3_ezf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1jm3_ezf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:layout-left" {...props}></Icon>
