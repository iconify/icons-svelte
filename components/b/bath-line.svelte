<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oho-25_re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oho-25_re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bath-line" {...props}></Icon>
