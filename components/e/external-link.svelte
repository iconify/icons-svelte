<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzwy0zbjv.css';
import '../../css/j/j7gs3mbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzwy0zbjv"/><path class="j7gs3mbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:external-link" {...props}></Icon>
