<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tygc8dbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tygc8dbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minus-filled" {...props}></Icon>
