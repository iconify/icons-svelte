<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsmyl7b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qsmyl7b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:charging-station-15" {...props}></Icon>
