<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7mmadcvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7mmadcvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gitkraken" {...props}></Icon>
