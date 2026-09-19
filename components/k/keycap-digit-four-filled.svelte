<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njp9bxbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="njp9bxbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-four-filled" {...props}></Icon>
