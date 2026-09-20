<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1l3iv1qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1l3iv1qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:more2" {...props}></Icon>
