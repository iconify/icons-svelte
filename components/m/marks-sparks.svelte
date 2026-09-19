<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldg4urbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldg4urbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:marks-sparks" {...props}></Icon>
