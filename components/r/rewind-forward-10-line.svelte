<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1vun7bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1vun7bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-forward-10-line" {...props}></Icon>
