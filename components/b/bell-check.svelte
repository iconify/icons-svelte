<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw4_wyw5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw4_wyw5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-check" {...props}></Icon>
