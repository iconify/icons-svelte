<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gklwl06rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gklwl06rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:linux-containers" {...props}></Icon>
