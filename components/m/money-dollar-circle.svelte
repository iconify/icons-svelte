<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1_to411n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q1_to411n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-dollar-circle" {...props}></Icon>
