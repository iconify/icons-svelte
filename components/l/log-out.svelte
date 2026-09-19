<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze8le8r9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze8le8r9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:log-out" {...props}></Icon>
