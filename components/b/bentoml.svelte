<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugtm5y13q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugtm5y13q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bentoml" {...props}></Icon>
