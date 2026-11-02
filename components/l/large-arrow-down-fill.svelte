<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t--3ic8dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t--3ic8dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-down-fill" {...props}></Icon>
