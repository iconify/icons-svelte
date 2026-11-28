<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmm7bu0st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmm7bu0st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chess-queen" {...props}></Icon>
