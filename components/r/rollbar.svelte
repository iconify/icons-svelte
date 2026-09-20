<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paek5_b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paek5_b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rollbar" {...props}></Icon>
