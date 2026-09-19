<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1fsr6i8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1fsr6i8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bathtub-filled" {...props}></Icon>
