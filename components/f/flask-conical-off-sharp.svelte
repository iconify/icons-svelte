<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw124pgac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw124pgac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-conical-off-sharp" {...props}></Icon>
