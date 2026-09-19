<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw6ff4bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="iw6ff4bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-zero" {...props}></Icon>
