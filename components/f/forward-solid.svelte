<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jho5y_bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jho5y_bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:forward-solid" {...props}></Icon>
