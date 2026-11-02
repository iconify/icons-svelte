<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqyy3pcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqyy3pcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-success-line" {...props}></Icon>
