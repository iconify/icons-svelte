<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kepdfhbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kepdfhbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:quote-down" {...props}></Icon>
