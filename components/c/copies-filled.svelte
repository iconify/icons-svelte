<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfz9rubqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cfz9rubqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:copies-filled" {...props}></Icon>
