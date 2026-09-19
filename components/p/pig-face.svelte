<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me6yobbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="me6yobbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pig-face" {...props}></Icon>
