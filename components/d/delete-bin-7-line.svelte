<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb_-dwb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_-dwb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-7-line" {...props}></Icon>
