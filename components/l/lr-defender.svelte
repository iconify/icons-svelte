<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg34fmb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg34fmb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lr-defender" {...props}></Icon>
