<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp37asbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pp37asbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-liga-small-filled" {...props}></Icon>
