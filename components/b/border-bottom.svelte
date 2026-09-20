<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rum1edbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rum1edbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:border-bottom" {...props}></Icon>
