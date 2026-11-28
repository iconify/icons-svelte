<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgn2e9haf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgn2e9haf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plug" {...props}></Icon>
