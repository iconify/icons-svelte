<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a949o57ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a949o57ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lego" {...props}></Icon>
