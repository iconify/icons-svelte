<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oip9e8p0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oip9e8p0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-3-line" {...props}></Icon>
