<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhgspibzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhgspibzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:airbus" {...props}></Icon>
