<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eye58abti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eye58abti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:connector-fill" {...props}></Icon>
