<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0b4gnb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0b4gnb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:android-filled" {...props}></Icon>
