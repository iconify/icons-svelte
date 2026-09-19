<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6r8ildcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6r8ildcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:avito" {...props}></Icon>
