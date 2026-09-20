<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfhr6oggz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfhr6oggz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:information-2-line" {...props}></Icon>
