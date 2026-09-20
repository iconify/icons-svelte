<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxva56-py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxva56-py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:corner-left-down" {...props}></Icon>
