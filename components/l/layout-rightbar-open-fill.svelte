<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtrxd9xag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtrxd9xag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-rightbar-open-fill" {...props}></Icon>
