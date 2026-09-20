<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gybadhj-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gybadhj-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lira-octagon-solid" {...props}></Icon>
