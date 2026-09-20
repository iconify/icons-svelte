<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrlg4dbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrlg4dbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:recycle" {...props}></Icon>
