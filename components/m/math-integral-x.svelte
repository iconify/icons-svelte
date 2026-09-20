<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsag7tpli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsag7tpli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-integral-x" {...props}></Icon>
