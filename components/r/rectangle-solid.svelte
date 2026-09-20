<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afl1-ubdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afl1-ubdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rectangle-solid" {...props}></Icon>
