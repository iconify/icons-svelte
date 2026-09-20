<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-c_r3bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l-c_r3bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:forward-circle" {...props}></Icon>
