<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-b2db31y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-b2db31y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:insights-24" {...props}></Icon>
