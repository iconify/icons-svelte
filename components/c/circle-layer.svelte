<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7w8lbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk7w8lbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:circle-layer" {...props}></Icon>
