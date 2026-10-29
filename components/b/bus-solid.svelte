<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzm2qigte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzm2qigte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bus-solid" {...props}></Icon>
