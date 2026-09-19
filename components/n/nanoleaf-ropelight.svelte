<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3o6zp8oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3o6zp8oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-ropelight" {...props}></Icon>
