<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgru19b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgru19b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:chevron-double-right" {...props}></Icon>
