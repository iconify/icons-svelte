<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n48inlb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n48inlb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-hogvind" {...props}></Icon>
