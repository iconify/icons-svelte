<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow28kisgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow28kisgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right2" {...props}></Icon>
