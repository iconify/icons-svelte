<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfzm3g0mg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfzm3g0mg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:navigation" {...props}></Icon>
