<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x559hlbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x559hlbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-trapeze" {...props}></Icon>
