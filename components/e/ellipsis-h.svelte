<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyw85fihm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyw85fihm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:ellipsis-h" {...props}></Icon>
