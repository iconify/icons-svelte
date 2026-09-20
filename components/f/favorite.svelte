<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixth9-o6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixth9-o6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:favorite" {...props}></Icon>
