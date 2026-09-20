<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4tztr9dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4tztr9dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-horiz-line" {...props}></Icon>
