<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvwi7cb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvwi7cb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lock-open" {...props}></Icon>
