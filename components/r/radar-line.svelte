<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek9gtazpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ek9gtazpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:radar-line" {...props}></Icon>
