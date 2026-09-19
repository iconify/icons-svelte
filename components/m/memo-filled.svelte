<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scojwrb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="scojwrb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:memo-filled" {...props}></Icon>
