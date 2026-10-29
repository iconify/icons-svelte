<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l725shb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l725shb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:power" {...props}></Icon>
