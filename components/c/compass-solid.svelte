<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crnq79b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crnq79b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:compass-solid" {...props}></Icon>
