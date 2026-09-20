<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe774vber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe774vber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:horizontal-align-left" {...props}></Icon>
