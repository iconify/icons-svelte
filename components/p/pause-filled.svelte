<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofwvx0evs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofwvx0evs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pause-filled" {...props}></Icon>
