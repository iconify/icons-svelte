<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4n1kbb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="l4n1kbb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:hourglass-f" {...props}></Icon>
