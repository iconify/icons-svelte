<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ry7yewp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m-ry7yewp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-eleven-small-filled" {...props}></Icon>
