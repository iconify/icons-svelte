<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh4bcoq2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh4bcoq2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:health-services" {...props}></Icon>
