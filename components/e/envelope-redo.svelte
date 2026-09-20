<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uong3y8dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uong3y8dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-redo" {...props}></Icon>
