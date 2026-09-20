<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_gqn-ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_gqn-ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dtube" {...props}></Icon>
