<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjz6dqb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vjz6dqb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:happy" {...props}></Icon>
