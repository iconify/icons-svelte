<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi8jfjbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi8jfjbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:focus-center-24" {...props}></Icon>
