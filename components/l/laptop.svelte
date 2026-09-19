<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui3celb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ui3celb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:laptop" {...props}></Icon>
