<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjc4c_b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rjc4c_b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pear-logo-small-filled" {...props}></Icon>
