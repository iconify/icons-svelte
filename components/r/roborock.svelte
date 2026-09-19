<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpfc-j4bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpfc-j4bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roborock" {...props}></Icon>
