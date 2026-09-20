<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liijiacut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="liijiacut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bell-slash-solid" {...props}></Icon>
