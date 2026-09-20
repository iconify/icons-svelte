<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a846-ybbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a846-ybbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:blazemeter" {...props}></Icon>
