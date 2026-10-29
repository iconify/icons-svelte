<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s24j4orns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s24j4orns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-corn-solid" {...props}></Icon>
