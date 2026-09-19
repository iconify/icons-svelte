<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc2k5s1mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2k5s1mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-door-open" {...props}></Icon>
