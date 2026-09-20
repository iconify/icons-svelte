<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5cc-ytzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5cc-ytzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:k6" {...props}></Icon>
