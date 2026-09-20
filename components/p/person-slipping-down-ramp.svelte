<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcqednb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kcqednb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-slipping-down-ramp" {...props}></Icon>
