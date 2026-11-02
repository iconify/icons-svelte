<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywp966rlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywp966rlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rainstorm-fill" {...props}></Icon>
