<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms8pr2b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ms8pr2b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pushpin-small-filled" {...props}></Icon>
