<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7btshbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m7btshbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-christian-15" {...props}></Icon>
