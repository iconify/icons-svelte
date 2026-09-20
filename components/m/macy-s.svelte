<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c69tr8boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c69tr8boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:macy-s" {...props}></Icon>
