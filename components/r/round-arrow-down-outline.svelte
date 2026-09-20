<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omu9mvuwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="omu9mvuwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-arrow-down-outline" {...props}></Icon>
