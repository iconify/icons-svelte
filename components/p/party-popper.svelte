<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_juk50dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_juk50dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:party-popper" {...props}></Icon>
