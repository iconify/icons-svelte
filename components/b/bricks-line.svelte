<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emr-nmmkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emr-nmmkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bricks-line" {...props}></Icon>
