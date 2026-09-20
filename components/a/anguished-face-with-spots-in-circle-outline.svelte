<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ricy93v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m6ricy93v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anguished-face-with-spots-in-circle-outline" {...props}></Icon>
