<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ymmubdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3ymmubdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:log-in" {...props}></Icon>
