<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rosx4zbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rosx4zbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:plus-circle" {...props}></Icon>
