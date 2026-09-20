<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddzs-grco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddzs-grco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chess-king-filled" {...props}></Icon>
