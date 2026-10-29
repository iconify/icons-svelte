<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oalh-698v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oalh-698v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-left-to-line-solid" {...props}></Icon>
