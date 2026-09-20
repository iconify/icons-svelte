<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp-n3fbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp-n3fbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aimass" {...props}></Icon>
