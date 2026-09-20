<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g89fqjb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g89fqjb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:first-aid-kit-off" {...props}></Icon>
