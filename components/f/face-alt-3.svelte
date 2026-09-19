<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-kbjab1h.css';
import '../../css/m/m95s5yi8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="m95s5yi8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt-3" {...props}></Icon>
