<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox8cu4u3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ox8cu4u3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clockwise-outline" {...props}></Icon>
