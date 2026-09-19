<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtx-1ee8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wtx-1ee8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-eight-filled" {...props}></Icon>
