<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-tn9nbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-tn9nbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:loopback" {...props}></Icon>
