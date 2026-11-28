<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itfot0bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itfot0bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:desklamp" {...props}></Icon>
