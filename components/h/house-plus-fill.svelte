<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p667ec9ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p667ec9ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-plus-fill" {...props}></Icon>
