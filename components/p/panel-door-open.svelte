<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybio2ac2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybio2ac2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:panel-door-open" {...props}></Icon>
