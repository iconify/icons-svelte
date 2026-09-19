<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt62d_b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt62d_b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:jar" {...props}></Icon>
