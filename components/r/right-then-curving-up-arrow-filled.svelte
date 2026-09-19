<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz-9f21ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bz-9f21ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-then-curving-up-arrow-filled" {...props}></Icon>
