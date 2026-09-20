<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dchr9fxqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dchr9fxqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jdoodle" {...props}></Icon>
