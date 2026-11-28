<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/req006c1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="req006c1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-x" {...props}></Icon>
