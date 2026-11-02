<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2-fsxbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2-fsxbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:caravan-line" {...props}></Icon>
