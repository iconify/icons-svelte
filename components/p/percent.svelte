<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbfbj7gjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbfbj7gjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:percent" {...props}></Icon>
