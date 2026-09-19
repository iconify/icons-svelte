<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at_li1b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="at_li1b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:party-popper-small" {...props}></Icon>
