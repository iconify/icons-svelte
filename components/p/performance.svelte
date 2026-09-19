<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp-1s5bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gp-1s5bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:performance" {...props}></Icon>
